<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2be6s9qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z2be6s9qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:js-square" {...props}></Icon>
