<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey1o4hbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey1o4hbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:microsoft" {...props}></Icon>
