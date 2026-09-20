<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cykb50bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cykb50bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-filled" {...props}></Icon>
