<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3-dh46ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3-dh46ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-alt-2-filled" {...props}></Icon>
