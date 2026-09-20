<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu8j9_fgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xu8j9_fgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jinear-dark" {...props}></Icon>
