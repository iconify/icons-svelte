<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zljz0d6td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zljz0d6td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reddit-dark" {...props}></Icon>
