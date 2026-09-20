<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dax8w86yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dax8w86yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-up-24" {...props}></Icon>
