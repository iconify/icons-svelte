<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl2rrkrrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl2rrkrrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christmas-hat-line" {...props}></Icon>
