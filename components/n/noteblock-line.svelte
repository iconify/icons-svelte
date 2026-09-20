<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6bb24tjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6bb24tjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:noteblock-line" {...props}></Icon>
