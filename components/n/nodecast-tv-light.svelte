<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8zj8i1eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f8zj8i1eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nodecast-tv-light" {...props}></Icon>
