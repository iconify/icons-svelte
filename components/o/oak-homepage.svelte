<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffqzsgefn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffqzsgefn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oak-homepage" {...props}></Icon>
