<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdp_xxbiy.css';
import '../../css/z/zutdd9mbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdp_xxbiy"/><path clip-rule="evenodd" class="zutdd9mbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-keyhole-minimalistic-outline" {...props}></Icon>
