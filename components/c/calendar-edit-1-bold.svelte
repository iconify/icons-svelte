<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjui_cb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjui_cb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:calendar-edit-1-bold" {...props}></Icon>
