<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnjf2ccpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnjf2ccpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-tie-voice" {...props}></Icon>
