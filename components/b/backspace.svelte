<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdt_h3a4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rdt_h3a4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:backspace" {...props}></Icon>
