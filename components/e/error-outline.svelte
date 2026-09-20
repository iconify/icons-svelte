<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzwll2x8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzwll2x8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:error-outline" {...props}></Icon>
