<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb76uabce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bb76uabce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:hubspot" {...props}></Icon>
