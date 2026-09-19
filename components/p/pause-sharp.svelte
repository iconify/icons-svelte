<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgh8nu16y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wgh8nu16y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pause-sharp" {...props}></Icon>
