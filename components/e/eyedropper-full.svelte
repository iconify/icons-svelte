<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq79_r4_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="sq79_r4_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:eyedropper-full" {...props}></Icon>
