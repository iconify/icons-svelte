<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5q0cbblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5q0cbblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiodeck-light" {...props}></Icon>
