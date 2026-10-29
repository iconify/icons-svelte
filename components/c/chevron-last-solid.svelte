<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gszfr8bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gszfr8bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-last-solid" {...props}></Icon>
