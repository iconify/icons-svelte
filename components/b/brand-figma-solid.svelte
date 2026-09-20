<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrsarig3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrsarig3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-figma-solid" {...props}></Icon>
