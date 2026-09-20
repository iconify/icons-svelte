<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu9v8ltiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iu9v8ltiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:native-button" {...props}></Icon>
