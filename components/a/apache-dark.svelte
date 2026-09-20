<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0csl3b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0csl3b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-dark" {...props}></Icon>
