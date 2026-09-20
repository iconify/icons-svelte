<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzz0615qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzz0615qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bluesky-dark" {...props}></Icon>
