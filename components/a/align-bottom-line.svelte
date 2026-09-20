<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-p6c476e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-p6c476e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-bottom-line" {...props}></Icon>
