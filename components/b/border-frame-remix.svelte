<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dccel2bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dccel2bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:border-frame-remix" {...props}></Icon>
