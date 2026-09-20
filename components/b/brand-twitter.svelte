<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrq3bhfat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrq3bhfat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-twitter" {...props}></Icon>
