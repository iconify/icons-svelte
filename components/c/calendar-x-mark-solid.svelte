<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_yb-6bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_yb-6bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-x-mark-solid" {...props}></Icon>
