<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la-8prbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="la-8prbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:batterysixty" {...props}></Icon>
