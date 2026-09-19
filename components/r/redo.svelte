<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twae0ibqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="twae0ibqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:redo" {...props}></Icon>
