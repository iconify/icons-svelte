<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpd0sxoqw.css';
import '../../css/z/z-nr2n3tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpd0sxoqw"/><path class="z-nr2n3tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gear-filled" {...props}></Icon>
