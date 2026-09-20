<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc7cseb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc7cseb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-tree-map-sharp" {...props}></Icon>
