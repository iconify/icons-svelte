<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa4bx0bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xa4bx0bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dashboard-circle" {...props}></Icon>
