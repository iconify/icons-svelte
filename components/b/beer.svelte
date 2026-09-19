<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn-h29jjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sn-h29jjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:beer" {...props}></Icon>
