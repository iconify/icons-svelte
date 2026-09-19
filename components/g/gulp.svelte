<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqsjmzzkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="lqsjmzzkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:gulp" {...props}></Icon>
