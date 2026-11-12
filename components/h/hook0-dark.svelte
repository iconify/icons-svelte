<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iopt-_0-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iopt-_0-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hook0-dark" {...props}></Icon>
