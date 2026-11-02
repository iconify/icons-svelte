<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsfernben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsfernben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-no-axes-combined-line" {...props}></Icon>
