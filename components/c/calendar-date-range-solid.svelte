<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuxx7n4ha.css';
import '../../css/x/xyaaz0bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuxx7n4ha"/><path clip-rule="evenodd" class="xyaaz0bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-date-range-solid" {...props}></Icon>
