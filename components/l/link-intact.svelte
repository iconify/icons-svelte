<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx1m91mzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lx1m91mzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:link-intact" {...props}></Icon>
