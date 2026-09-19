<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt-b6obyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wt-b6obyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:heart-broken" {...props}></Icon>
