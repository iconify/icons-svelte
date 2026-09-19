<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7sxkpvxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7sxkpvxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-window" {...props}></Icon>
