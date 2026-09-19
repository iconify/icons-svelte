<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m134ul6od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m134ul6od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:icon-sets-flag" {...props}></Icon>
