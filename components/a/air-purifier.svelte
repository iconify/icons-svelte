<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxo43ab3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxo43ab3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:air-purifier" {...props}></Icon>
