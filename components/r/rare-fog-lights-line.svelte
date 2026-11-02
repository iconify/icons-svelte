<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbf7qdnvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbf7qdnvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rare-fog-lights-line" {...props}></Icon>
