<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yepbyis8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yepbyis8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-classic-3" {...props}></Icon>
