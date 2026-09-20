<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hott3ac_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hott3ac_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:meta-line" {...props}></Icon>
