<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvtem461l.css';
import '../../css/t/tcz9p2b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vvtem461l"/><path class="tcz9p2b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-clone-16" {...props}></Icon>
