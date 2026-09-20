<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9cehxl3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9cehxl3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-charging-2" {...props}></Icon>
