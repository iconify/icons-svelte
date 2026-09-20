<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2j1l3yzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2j1l3yzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-p-circle" {...props}></Icon>
