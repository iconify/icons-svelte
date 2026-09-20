<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt_9hnz1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vt_9hnz1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fandango-light" {...props}></Icon>
