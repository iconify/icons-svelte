<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti44kjihb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ti44kjihb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-forked-16" {...props}></Icon>
