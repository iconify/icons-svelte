<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isrno4bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isrno4bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-no-axes-gantt" {...props}></Icon>
