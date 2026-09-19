<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbyuj8lph.css';
import '../../css/e/eldvjb07a.css';
import '../../css/n/n-qmf6rfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rbyuj8lph"/><path class="eldvjb07a"/><path class="n-qmf6rfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-wordpress" {...props}></Icon>
