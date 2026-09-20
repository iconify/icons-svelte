<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fisikzwzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fisikzwzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-g-waves-solid" {...props}></Icon>
