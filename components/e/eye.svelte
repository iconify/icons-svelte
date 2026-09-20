<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzwajx60y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xzwajx60y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:eye" {...props}></Icon>
