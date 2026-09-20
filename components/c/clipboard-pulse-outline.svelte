<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl8v88buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl8v88buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-pulse-outline" {...props}></Icon>
