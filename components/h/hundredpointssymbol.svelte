<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-1tk425g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-1tk425g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hundredpointssymbol" {...props}></Icon>
