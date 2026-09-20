<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j35574bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j35574bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-circle-filled" {...props}></Icon>
