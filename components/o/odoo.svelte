<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8d3g7dez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8d3g7dez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:odoo" {...props}></Icon>
