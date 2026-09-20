<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q44nenbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q44nenbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-question" {...props}></Icon>
