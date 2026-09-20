<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jle5wnflo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="jle5wnflo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:police-jp-11" {...props}></Icon>
