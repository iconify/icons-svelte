<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwwft199d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bwwft199d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:page4" {...props}></Icon>
