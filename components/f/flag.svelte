<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pshecz_7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":384};
const content = `<path class="pshecz_7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flag" {...props}></Icon>
