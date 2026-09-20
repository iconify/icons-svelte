<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z82ysocfk.css';
import '../../css/h/h0h1ev4io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z82ysocfk"/><path class="h0h1ev4io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kilt" {...props}></Icon>
