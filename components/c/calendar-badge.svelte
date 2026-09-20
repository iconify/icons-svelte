<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3n8nacaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3n8nacaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-badge" {...props}></Icon>
