<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6y37ac6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6y37ac6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cadenza-dark" {...props}></Icon>
