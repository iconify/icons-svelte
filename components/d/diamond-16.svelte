<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p13hrnsvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p13hrnsvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diamond-16" {...props}></Icon>
