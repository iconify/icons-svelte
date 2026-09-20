<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8h15bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pa8h15bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:part-db" {...props}></Icon>
