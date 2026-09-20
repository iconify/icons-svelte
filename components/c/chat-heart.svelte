<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lcg626bqg.css';
import '../../css/i/i7_qlrbtz.css';
import '../../css/m/miqf99bxq.css';
import '../../css/r/rmxdniboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lcg626bqg"/><path clip-rule="evenodd" class="i7_qlrbtz"/><path class="miqf99bxq"/><path clip-rule="evenodd" class="rmxdniboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-heart" {...props}></Icon>
