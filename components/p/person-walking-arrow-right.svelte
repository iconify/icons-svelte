<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-iqkzb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c-iqkzb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-walking-arrow-right" {...props}></Icon>
