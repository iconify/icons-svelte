<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0sgjwbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l0sgjwbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentelemetry-dark" {...props}></Icon>
