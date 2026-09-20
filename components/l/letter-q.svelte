<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1t1a4bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1t1a4bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-q" {...props}></Icon>
