<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqsf3pbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqsf3pbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-3-fill" {...props}></Icon>
