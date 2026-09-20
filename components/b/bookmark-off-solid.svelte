<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk_wx9b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk_wx9b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bookmark-off-solid" {...props}></Icon>
