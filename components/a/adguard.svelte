<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mim_u7m5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mim_u7m5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:adguard" {...props}></Icon>
