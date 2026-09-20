<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9773-b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e9773-b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:joystick-outline" {...props}></Icon>
