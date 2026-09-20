<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a85qzclsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a85qzclsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:moon-16" {...props}></Icon>
