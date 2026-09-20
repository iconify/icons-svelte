<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haqr67bmp.css';
import '../../css/z/z3jvyi2th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haqr67bmp"/><path class="z3jvyi2th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-down-line" {...props}></Icon>
