<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btq232bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="btq232bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:dot-net" {...props}></Icon>
