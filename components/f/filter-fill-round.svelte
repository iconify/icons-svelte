<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcc8lpl6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcc8lpl6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:filter-fill-round" {...props}></Icon>
