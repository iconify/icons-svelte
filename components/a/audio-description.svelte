<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyi47_3sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xyi47_3sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:audio-description" {...props}></Icon>
