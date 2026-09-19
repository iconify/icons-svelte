<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vomss_b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vomss_b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:heart-broken" {...props}></Icon>
