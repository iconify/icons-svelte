<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be780fp0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="be780fp0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:coins" {...props}></Icon>
