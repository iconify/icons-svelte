<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu9emeb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bu9emeb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:clockwisedownupcircledarrows" {...props}></Icon>
