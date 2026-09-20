<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt9wlnusq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9wlnusq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-week" {...props}></Icon>
