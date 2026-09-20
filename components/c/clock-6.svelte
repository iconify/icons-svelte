<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf03oqols.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf03oqols"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-6" {...props}></Icon>
