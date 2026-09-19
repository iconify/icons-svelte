<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9en5ccwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9en5ccwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:phoscon" {...props}></Icon>
