<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii08xxbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii08xxbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-x" {...props}></Icon>
