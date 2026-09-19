<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk4migb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk4migb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-justify-end" {...props}></Icon>
