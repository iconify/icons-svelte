<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aerx4bbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aerx4bbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-anticlockwise-1-line" {...props}></Icon>
