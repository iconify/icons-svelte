<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9g4_sbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x9g4_sbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:posthog-light" {...props}></Icon>
