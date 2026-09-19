<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxlo_dguu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="pxlo_dguu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:crop" {...props}></Icon>
