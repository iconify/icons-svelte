<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkp95sn_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkp95sn_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opel" {...props}></Icon>
