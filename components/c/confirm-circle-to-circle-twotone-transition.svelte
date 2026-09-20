<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/k/kcsuak.css';
import '../../css/y/yp2axg.css';
import '../../css/f/fill-from-0.css';
import '../../css/s/so-to-14.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew kcsuak"/><path class="iw1iew yp2axg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:confirm-circle-to-circle-twotone-transition" {...props}></Icon>
