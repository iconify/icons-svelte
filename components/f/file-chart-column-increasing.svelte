<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj6m8xbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj6m8xbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-chart-column-increasing" {...props}></Icon>
