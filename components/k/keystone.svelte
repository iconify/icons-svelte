<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdpazwbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdpazwbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:keystone" {...props}></Icon>
