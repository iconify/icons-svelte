<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6lfp1icm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6lfp1icm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-info" {...props}></Icon>
