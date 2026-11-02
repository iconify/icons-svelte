<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqzc2vbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqzc2vbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-expansion-fill" {...props}></Icon>
