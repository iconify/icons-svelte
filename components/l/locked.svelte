<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvcs4u9hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvcs4u9hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:locked" {...props}></Icon>
