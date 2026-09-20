<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_w_2druv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t_w_2druv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-sun" {...props}></Icon>
