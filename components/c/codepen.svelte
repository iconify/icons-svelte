<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk3dtpmsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nk3dtpmsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:codepen" {...props}></Icon>
