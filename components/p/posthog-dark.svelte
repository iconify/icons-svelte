<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4pv2vbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4pv2vbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:posthog-dark" {...props}></Icon>
