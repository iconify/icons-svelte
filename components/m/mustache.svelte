<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcr5_ubdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcr5_ubdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mustache" {...props}></Icon>
