<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj3z4_bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj3z4_bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-off" {...props}></Icon>
