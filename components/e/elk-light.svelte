<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwh--inlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwh--inlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elk-light" {...props}></Icon>
