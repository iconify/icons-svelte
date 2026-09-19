<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy6bk_bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uy6bk_bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:calendar-fill-12" {...props}></Icon>
