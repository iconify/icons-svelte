<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6i5ey9la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6i5ey9la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-minus-outline" {...props}></Icon>
