<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avwo5dbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avwo5dbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:filter-line" {...props}></Icon>
