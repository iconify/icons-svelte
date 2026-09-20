<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2nvnvk-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i2nvnvk-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:calendar-x-outline" {...props}></Icon>
