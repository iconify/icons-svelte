<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bafzvub8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bafzvub8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-evergreen-light" {...props}></Icon>
