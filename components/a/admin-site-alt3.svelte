<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xst-acckn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xst-acckn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-site-alt3" {...props}></Icon>
