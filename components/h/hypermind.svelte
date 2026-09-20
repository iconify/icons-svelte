<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl80vxbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pl80vxbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hypermind" {...props}></Icon>
