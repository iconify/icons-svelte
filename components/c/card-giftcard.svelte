<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq0na3ryh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="jq0na3ryh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:card-giftcard" {...props}></Icon>
