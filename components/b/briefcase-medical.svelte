<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scum1rbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scum1rbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:briefcase-medical" {...props}></Icon>
