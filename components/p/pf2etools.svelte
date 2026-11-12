<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksigsecyg.css';
import '../../css/y/y-4aifk4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksigsecyg"/><path class="y-4aifk4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pf2etools" {...props}></Icon>
