<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh_vbsbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wh_vbsbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:protocols" {...props}></Icon>
