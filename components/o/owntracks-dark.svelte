<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deto26p-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="deto26p-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:owntracks-dark" {...props}></Icon>
