<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1yz3bbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r1yz3bbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-astonished-fill" {...props}></Icon>
