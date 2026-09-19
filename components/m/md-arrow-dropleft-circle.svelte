<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp_xnxhpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jp_xnxhpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-arrow-dropleft-circle" {...props}></Icon>
