<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l823qg8ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l823qg8ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pennant-2" {...props}></Icon>
