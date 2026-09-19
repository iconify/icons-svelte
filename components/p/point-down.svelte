<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li4g1kbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="li4g1kbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:point-down" {...props}></Icon>
