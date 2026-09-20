<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfkdpjbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfkdpjbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mbin-dark" {...props}></Icon>
