<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_a55lb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1408};
const content = `<path class="z_a55lb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:qrcode" {...props}></Icon>
