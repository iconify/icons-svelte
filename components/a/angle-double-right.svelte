<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6umq1pek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="w6umq1pek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:angle-double-right" {...props}></Icon>
