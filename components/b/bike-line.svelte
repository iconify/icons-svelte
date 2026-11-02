<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta9xpugyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta9xpugyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bike-line" {...props}></Icon>
