<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m63ldrfkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m63ldrfkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:desktop" {...props}></Icon>
