<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ezq80-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9ezq80-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-4-line" {...props}></Icon>
