<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksa1a5y2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksa1a5y2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:feeder-fill" {...props}></Icon>
