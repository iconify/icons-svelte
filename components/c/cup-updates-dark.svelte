<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3o53phlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i3o53phlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cup-updates-dark" {...props}></Icon>
