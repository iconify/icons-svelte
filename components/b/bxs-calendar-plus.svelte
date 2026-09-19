<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt_9ord6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt_9ord6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-calendar-plus" {...props}></Icon>
