<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogx6jxblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ogx6jxblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bridge-circle-exclamation" {...props}></Icon>
