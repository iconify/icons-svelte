<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bthx506go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bthx506go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-down-circle-fill" {...props}></Icon>
