<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la4yf5w1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la4yf5w1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:download" {...props}></Icon>
