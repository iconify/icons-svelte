<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1o_rnbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1o_rnbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-alert-outline" {...props}></Icon>
