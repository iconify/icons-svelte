<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1wdc4nuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1wdc4nuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-time" {...props}></Icon>
