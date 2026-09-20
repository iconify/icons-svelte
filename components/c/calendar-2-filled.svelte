<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3sc48a3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3sc48a3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-2-filled" {...props}></Icon>
