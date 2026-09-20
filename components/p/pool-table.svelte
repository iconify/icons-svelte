<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh-4zob8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh-4zob8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pool-table" {...props}></Icon>
