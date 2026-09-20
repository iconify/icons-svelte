<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os1ydj4cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os1ydj4cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:door-closed-solid" {...props}></Icon>
