<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3gi5bchw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3gi5bchw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:part-of-circle-5" {...props}></Icon>
