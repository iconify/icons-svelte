<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9xce2utg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9xce2utg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:move-to-bottom-16" {...props}></Icon>
