<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbj30sd-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbj30sd-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-warning" {...props}></Icon>
