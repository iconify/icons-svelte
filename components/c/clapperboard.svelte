<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd9e6acip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xd9e6acip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:clapperboard" {...props}></Icon>
