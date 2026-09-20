<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc83tyb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sc83tyb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docassemble-light" {...props}></Icon>
