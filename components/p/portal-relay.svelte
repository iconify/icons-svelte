<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deuoqgbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="deuoqgbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portal-relay" {...props}></Icon>
