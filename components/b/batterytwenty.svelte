<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ojy9bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="i9ojy9bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:batterytwenty" {...props}></Icon>
