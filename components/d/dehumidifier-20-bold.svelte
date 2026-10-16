<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp_3l1bkn.css';
import '../../css/k/kyukd-byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fp_3l1bkn"/><path class="kyukd-byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dehumidifier-20-bold" {...props}></Icon>
