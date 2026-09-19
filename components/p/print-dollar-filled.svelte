<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0tz-gtwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0tz-gtwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:print-dollar-filled" {...props}></Icon>
