<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5r6o_bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5r6o_bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:live-blog" {...props}></Icon>
