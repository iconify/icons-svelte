<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3w13jb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3w13jb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-refresh" {...props}></Icon>
