<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc72tnbzk.css';
import '../../css/i/i3fanzlul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc72tnbzk"/><path class="i3fanzlul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rootstock" {...props}></Icon>
