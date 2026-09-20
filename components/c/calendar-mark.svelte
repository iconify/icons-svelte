<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytk0fdbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytk0fdbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:calendar-mark" {...props}></Icon>
