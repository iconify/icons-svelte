<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_woru4wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l_woru4wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nasa-worm-light" {...props}></Icon>
