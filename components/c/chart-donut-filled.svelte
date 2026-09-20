<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj9s757sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj9s757sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-donut-filled" {...props}></Icon>
