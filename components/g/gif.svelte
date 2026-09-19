<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1o8dn6qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="w1o8dn6qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:gif" {...props}></Icon>
