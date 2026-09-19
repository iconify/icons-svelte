<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6obxeb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6obxeb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-wide" {...props}></Icon>
