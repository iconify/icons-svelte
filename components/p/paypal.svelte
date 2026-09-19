<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo5iq53rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="uo5iq53rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:paypal" {...props}></Icon>
