<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vby9crrze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vby9crrze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:downtify-dark" {...props}></Icon>
