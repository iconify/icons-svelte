<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq4tbcbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":480};
const content = `<path class="vq4tbcbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:friendfeed" {...props}></Icon>
