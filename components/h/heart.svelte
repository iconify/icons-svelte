<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wweh_w-kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="wweh_w-kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:heart" {...props}></Icon>
