<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc19e372j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mc19e372j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:leanpub" {...props}></Icon>
