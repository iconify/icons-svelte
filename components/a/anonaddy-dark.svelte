<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rssfh2bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rssfh2bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anonaddy-dark" {...props}></Icon>
