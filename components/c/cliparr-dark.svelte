<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nprivq5wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nprivq5wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cliparr-dark" {...props}></Icon>
