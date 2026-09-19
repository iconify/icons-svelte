<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaoovlbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zaoovlbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-rewind-outline" {...props}></Icon>
