<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0jo-47we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0jo-47we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-pause" {...props}></Icon>
