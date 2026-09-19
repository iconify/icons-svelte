<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj69l1b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj69l1b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-x-filled" {...props}></Icon>
