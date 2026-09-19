<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znqa3p1ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="znqa3p1ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:hooli" {...props}></Icon>
