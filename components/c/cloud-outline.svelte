<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wea8hpbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="wea8hpbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cloud-outline" {...props}></Icon>
