<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v15m2hbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v15m2hbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:move" {...props}></Icon>
