<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9-pb7c_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9-pb7c_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-help" {...props}></Icon>
