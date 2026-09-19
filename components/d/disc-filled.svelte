<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3bxagnhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3bxagnhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:disc-filled" {...props}></Icon>
