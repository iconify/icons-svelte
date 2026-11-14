<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ibcag14it.css';
import '../../css/w/wsanqobsx.css';
import '../../css/y/ybspv9stl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ibcag14it"/><path class="wsanqobsx"/><path class="ybspv9stl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camera-smile-01" {...props}></Icon>
