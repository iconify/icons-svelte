<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puid7l1ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="puid7l1ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:options" {...props}></Icon>
