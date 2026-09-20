<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgogo8ipx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgogo8ipx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:biohazard-solid" {...props}></Icon>
