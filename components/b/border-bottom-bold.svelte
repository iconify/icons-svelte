<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qniucrb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qniucrb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-bottom-bold" {...props}></Icon>
