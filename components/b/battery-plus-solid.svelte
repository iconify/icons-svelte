<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fewvsfb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fewvsfb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-plus-solid" {...props}></Icon>
