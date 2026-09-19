<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovon6wixu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovon6wixu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-check-01" {...props}></Icon>
