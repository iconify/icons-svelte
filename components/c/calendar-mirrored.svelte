<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldso4pdyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ldso4pdyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:calendar-mirrored" {...props}></Icon>
