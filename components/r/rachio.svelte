<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbirl8byl.css';
import '../../css/h/h546kdb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jbirl8byl"/><path class="h546kdb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rachio" {...props}></Icon>
