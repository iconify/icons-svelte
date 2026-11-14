<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4paw-bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4paw-bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart-add" {...props}></Icon>
