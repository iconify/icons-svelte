<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an1b2abwc.css';
import '../../css/a/aez-bmivh.css';
import '../../css/x/xo56y0b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an1b2abwc"/><path clip-rule="evenodd" class="aez-bmivh"/><path class="xo56y0b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-vertical-outline" {...props}></Icon>
