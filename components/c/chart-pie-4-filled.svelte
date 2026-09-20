<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq0-71bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0-71bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-pie-4-filled" {...props}></Icon>
