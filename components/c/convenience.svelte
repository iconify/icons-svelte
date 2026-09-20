<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-lza5ren.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s-lza5ren"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:convenience" {...props}></Icon>
