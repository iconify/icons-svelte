<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go4klvj4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="go4klvj4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:batterycharging" {...props}></Icon>
