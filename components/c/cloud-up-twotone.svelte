<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra8x7z.css';
import '../../css/a/a0m25c.css';
import '../../css/q/qjmzsy.css';
import '../../css/c/cn_flp.css';
import '../../css/l/l_ywrm.css';
import '../../css/x/x27gon.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra8x7z"/><path class="a0m25c qjmzsy"/><path class="a0m25c cn_flp"/><path class="a0m25c l_ywrm"/><path class="a0m25c x27gon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:cloud-up-twotone" {...props}></Icon>
