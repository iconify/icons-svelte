<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwv90wbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwv90wbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:minus" {...props}></Icon>
