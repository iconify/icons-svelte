<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hazr2xbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hazr2xbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:garage-dark" {...props}></Icon>
