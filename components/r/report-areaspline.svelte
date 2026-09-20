<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlyxuac-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlyxuac-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:report-areaspline" {...props}></Icon>
