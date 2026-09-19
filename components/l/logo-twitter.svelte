<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_m5myd5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l_m5myd5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-twitter" {...props}></Icon>
