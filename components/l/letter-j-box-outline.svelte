<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npe-89b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npe-89b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-j-box-outline" {...props}></Icon>
