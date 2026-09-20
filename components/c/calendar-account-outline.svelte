<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mucxzdmrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mucxzdmrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-account-outline" {...props}></Icon>
