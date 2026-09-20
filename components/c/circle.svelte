<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfn4_0bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfn4_0bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:circle" {...props}></Icon>
