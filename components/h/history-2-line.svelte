<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-o6yib2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-o6yib2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:history-2-line" {...props}></Icon>
