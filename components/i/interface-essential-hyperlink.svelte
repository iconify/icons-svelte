<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlr20m9qu.css';
import '../../css/a/av3hfsqru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rlr20m9qu"/><path class="av3hfsqru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-hyperlink" {...props}></Icon>
