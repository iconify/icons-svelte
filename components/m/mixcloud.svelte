<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6annib7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="k6annib7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:mixcloud" {...props}></Icon>
