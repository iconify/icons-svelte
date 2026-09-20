<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztliwnwek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztliwnwek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:calendar-plus-solid" {...props}></Icon>
