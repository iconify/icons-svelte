<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1hr6bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr1hr6bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-minus" {...props}></Icon>
