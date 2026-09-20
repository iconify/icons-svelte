<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7ehs_32k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t7ehs_32k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:riven-light" {...props}></Icon>
