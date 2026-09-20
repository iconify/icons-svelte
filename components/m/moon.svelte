<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir8d_s7hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ir8d_s7hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:moon" {...props}></Icon>
