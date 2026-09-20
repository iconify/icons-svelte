<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vplqfveod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vplqfveod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:manhole-cover-with-hydrant" {...props}></Icon>
