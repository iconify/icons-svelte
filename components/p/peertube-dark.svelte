<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b98gg_91s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b98gg_91s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peertube-dark" {...props}></Icon>
