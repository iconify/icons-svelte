<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro_yicc4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ro_yicc4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amazon-prime-video-logo-2-block" {...props}></Icon>
