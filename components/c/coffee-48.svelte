<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfg1jelsz.css';
import '../../css/f/fec_ntl8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pfg1jelsz"/><path class="fec_ntl8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coffee-48" {...props}></Icon>
