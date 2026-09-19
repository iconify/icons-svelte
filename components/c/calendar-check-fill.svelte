<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tul49hb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tul49hb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-check-fill" {...props}></Icon>
