<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxalaab1z.css';
import '../../css/y/yxo0gabyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxalaab1z"/><path clip-rule="evenodd" class="yxo0gabyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-bold-duotone" {...props}></Icon>
