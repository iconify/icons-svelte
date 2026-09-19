<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksa2hs06o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ksa2hs06o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:linkedin" {...props}></Icon>
