<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt1twzbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wt1twzbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:meter-16" {...props}></Icon>
