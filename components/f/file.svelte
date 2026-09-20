<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9sg1poyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m9sg1poyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file" {...props}></Icon>
