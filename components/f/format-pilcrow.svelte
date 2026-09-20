<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4ylb3_td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ylb3_td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-pilcrow" {...props}></Icon>
