<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcco9vbwq.css';
import '../../css/l/l5p8g7bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcco9vbwq"/><path class="l5p8g7bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-people-person-bubble-square-2" {...props}></Icon>
