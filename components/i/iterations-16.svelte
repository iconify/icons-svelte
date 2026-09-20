<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3u-g3b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g3u-g3b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:iterations-16" {...props}></Icon>
