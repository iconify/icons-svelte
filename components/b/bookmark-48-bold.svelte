<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ue9wb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b7ue9wb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-48-bold" {...props}></Icon>
