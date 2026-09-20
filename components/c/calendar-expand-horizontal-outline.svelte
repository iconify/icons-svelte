<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paivumq6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paivumq6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-expand-horizontal-outline" {...props}></Icon>
