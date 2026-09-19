<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ean2-obmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ean2-obmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:popup" {...props}></Icon>
