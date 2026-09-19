<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl470_b0c.css';
import '../../css/x/xgglfabho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl470_b0c"/><path class="xgglfabho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-ring" {...props}></Icon>
