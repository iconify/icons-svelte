<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4fj89t1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="q4fj89t1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fish-fins" {...props}></Icon>
