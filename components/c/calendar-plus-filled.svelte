<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/expzhk9as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="expzhk9as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-plus-filled" {...props}></Icon>
