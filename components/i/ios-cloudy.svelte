<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiktcnb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uiktcnb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloudy" {...props}></Icon>
