<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg7-xdbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hg7-xdbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pin-16" {...props}></Icon>
