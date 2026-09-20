<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn8k5hbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn8k5hbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-0" {...props}></Icon>
