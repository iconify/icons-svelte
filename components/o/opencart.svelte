<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obyc_pxxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2336,"height":1664};
const content = `<path class="obyc_pxxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:opencart" {...props}></Icon>
