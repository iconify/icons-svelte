<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw0njuuzd.css';
import '../../css/r/rssdfuhft.css';
import '../../css/y/ywin52edh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qw0njuuzd"/><path class="rssdfuhft"/><path class="ywin52edh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:doctrine-wordmark" {...props}></Icon>
