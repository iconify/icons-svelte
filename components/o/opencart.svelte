<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nus_c7byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nus_c7byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:opencart" {...props}></Icon>
