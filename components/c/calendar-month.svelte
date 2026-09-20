<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiv490bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiv490bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-month" {...props}></Icon>
