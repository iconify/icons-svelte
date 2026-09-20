<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr_y9gxnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr_y9gxnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:helix" {...props}></Icon>
