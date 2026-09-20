<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq20hybaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="iq20hybaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:direction-up" {...props}></Icon>
