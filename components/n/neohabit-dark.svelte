<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd5pp1qjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gd5pp1qjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:neohabit-dark" {...props}></Icon>
