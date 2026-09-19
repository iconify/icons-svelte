<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y59k7xduf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y59k7xduf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-x-square" {...props}></Icon>
