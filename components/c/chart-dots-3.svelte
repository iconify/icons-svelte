<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l27my8epx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l27my8epx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-dots-3" {...props}></Icon>
