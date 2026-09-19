<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh3b75c1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="xh3b75c1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bowl" {...props}></Icon>
