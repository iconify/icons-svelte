<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfat7mbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfat7mbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:poznote-light" {...props}></Icon>
