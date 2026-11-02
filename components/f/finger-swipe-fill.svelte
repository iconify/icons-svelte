<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo_5oivmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo_5oivmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-swipe-fill" {...props}></Icon>
