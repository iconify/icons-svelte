<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-lfmccxy.css';
import '../../css/p/pn4efebvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i-lfmccxy"/><path class="pn4efebvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:book-locked-16" {...props}></Icon>
