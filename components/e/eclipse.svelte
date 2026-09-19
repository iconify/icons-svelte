<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muu7-ibcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muu7-ibcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:eclipse" {...props}></Icon>
