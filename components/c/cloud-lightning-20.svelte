<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf4h7lvmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lf4h7lvmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-lightning-20" {...props}></Icon>
