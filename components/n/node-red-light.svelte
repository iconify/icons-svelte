<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru6tesmyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ru6tesmyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:node-red-light" {...props}></Icon>
