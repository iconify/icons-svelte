<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlhd07b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlhd07b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-fill" {...props}></Icon>
