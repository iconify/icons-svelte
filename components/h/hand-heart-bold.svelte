<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgs-libjk.css';
import '../../css/o/oam048mkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgs-libjk"/><path class="oam048mkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-heart-bold" {...props}></Icon>
