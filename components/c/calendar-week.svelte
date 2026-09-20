<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9bm9xb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a9bm9xb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:calendar-week" {...props}></Icon>
