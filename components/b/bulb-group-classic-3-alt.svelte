<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j01_ov-ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j01_ov-ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-classic-3-alt" {...props}></Icon>
