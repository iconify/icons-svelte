<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjtkvdbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="qjtkvdbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-801" {...props}></Icon>
