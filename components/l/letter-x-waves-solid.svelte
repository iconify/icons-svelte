<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cywaoh12c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cywaoh12c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x-waves-solid" {...props}></Icon>
