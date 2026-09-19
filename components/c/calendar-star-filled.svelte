<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmasy2qqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmasy2qqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-star-filled" {...props}></Icon>
