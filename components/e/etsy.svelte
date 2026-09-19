<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv8zs-_oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bv8zs-_oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:etsy" {...props}></Icon>
