<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksigsecyg.css';
import '../../css/s/si0nt0a3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksigsecyg"/><path class="si0nt0a3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pf2etools" {...props}></Icon>
