<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p06nvcb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p06nvcb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asrock-light" {...props}></Icon>
