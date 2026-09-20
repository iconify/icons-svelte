<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgti71m4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zgti71m4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fragile" {...props}></Icon>
