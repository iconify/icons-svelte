<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4h_36bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4h_36bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-secure-outline" {...props}></Icon>
