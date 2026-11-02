<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p96xxynhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p96xxynhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-3-line" {...props}></Icon>
