<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm1m7zb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wm1m7zb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:briefcasethree" {...props}></Icon>
