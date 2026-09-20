<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiipxcb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xiipxcb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prunemate-dark" {...props}></Icon>
