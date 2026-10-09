<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo64yvbkk.css';
import '../../css/r/r5qp9ebil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xo64yvbkk"/><path class="r5qp9ebil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pencil-48" {...props}></Icon>
