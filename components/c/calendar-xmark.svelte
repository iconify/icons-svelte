<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfym00_ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nfym00_ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:calendar-xmark" {...props}></Icon>
