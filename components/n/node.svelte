<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn-c7l4th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="sn-c7l4th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:node" {...props}></Icon>
