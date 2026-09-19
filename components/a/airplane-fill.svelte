<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uasa_bcbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uasa_bcbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:airplane-fill" {...props}></Icon>
