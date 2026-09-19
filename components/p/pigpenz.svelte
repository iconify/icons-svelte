<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd_hi_bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1024};
const content = `<path class="zd_hi_bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pigpenz" {...props}></Icon>
