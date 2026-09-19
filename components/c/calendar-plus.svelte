<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjt_1vbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjt_1vbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:calendar-plus" {...props}></Icon>
