<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5ml-gbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5ml-gbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netonnet-dark" {...props}></Icon>
