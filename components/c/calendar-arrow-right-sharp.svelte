<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xddbcbb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xddbcbb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-right-sharp" {...props}></Icon>
