<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2cgykpmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="u2cgykpmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:angle-left" {...props}></Icon>
