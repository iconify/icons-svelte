<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n814-dbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="n814-dbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chair" {...props}></Icon>
