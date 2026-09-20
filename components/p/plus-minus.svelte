<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibjd92y_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ibjd92y_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:plus-minus" {...props}></Icon>
