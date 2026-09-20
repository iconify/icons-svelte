<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmy012_jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmy012_jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:compass-fill" {...props}></Icon>
