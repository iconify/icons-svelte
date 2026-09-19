<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1a4_5bhx.css';
import '../../css/f/f0n61bjwo.css';
import '../../css/r/rdndzccdo.css';
import '../../css/v/vpbsv_3oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1a4_5bhx"/><path class="f0n61bjwo"/><path class="rdndzccdo"/><path class="vpbsv_3oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackhardshellfloppy" {...props}></Icon>
