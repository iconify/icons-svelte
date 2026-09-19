<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr2asabhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="nr2asabhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-holding-usd" {...props}></Icon>
