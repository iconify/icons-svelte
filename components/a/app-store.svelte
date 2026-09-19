<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjyxxf14t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjyxxf14t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:app-store" {...props}></Icon>
