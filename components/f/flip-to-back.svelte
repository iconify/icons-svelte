<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db1by81sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="db1by81sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flip-to-back" {...props}></Icon>
