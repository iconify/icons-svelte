<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l16p_0smn.css';
import '../../css/i/ilq4zvino.css';
import '../../css/o/otz3qz_jq.css';
import '../../css/l/l2qt7co3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l16p_0smn"/><path class="ilq4zvino"/><path class="otz3qz_jq"/><path class="l2qt7co3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-wifi-angle-bold-duotone" {...props}></Icon>
