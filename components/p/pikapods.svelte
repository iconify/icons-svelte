<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tufwuf_6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tufwuf_6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pikapods" {...props}></Icon>
