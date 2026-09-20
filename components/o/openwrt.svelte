<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frj4bs8az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frj4bs8az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openwrt" {...props}></Icon>
