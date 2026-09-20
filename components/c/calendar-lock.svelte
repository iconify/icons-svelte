<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0pyh4m-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0pyh4m-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-lock" {...props}></Icon>
