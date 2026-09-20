<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de_jx0dbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de_jx0dbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-charging-two" {...props}></Icon>
