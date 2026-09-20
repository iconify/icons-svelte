<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd88rekga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kd88rekga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hi-events-dark" {...props}></Icon>
