<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhy62g6ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhy62g6ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-off-filled" {...props}></Icon>
