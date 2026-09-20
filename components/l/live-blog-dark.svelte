<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fui6c76in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fui6c76in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:live-blog-dark" {...props}></Icon>
