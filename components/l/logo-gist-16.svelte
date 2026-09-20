<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxeawbdpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":16};
const content = `<path class="wxeawbdpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:logo-gist-16" {...props}></Icon>
