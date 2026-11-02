<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hczh8rbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hczh8rbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:banana-fill" {...props}></Icon>
