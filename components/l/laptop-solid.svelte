<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbsoh586u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kbsoh586u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:laptop-solid" {...props}></Icon>
