<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2nhvg7mm.css';
import '../../css/n/ny4n5ccbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2nhvg7mm"/><path class="ny4n5ccbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ocular" {...props}></Icon>
