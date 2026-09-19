<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp035-4hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="xp035-4hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:greater-than" {...props}></Icon>
