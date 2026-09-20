<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v96cw_iaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v96cw_iaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:imessage-logo-solid" {...props}></Icon>
