<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih_w5bcgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ih_w5bcgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:calendar-warning-remix" {...props}></Icon>
