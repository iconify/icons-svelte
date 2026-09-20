<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tykd_mbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tykd_mbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-usd-outline" {...props}></Icon>
