<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_uxkxb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z_uxkxb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:calendar-day" {...props}></Icon>
