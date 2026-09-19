<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwl6l_b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hwl6l_b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:j2x-outline" {...props}></Icon>
