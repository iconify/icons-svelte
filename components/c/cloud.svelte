<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj1k-xb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bj1k-xb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloud" {...props}></Icon>
