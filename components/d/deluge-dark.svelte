<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo8dgxbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jo8dgxbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:deluge-dark" {...props}></Icon>
