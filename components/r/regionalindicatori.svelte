<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilj6i9a_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilj6i9a_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatori" {...props}></Icon>
