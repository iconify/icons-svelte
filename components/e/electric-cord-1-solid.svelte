<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns28zkbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ns28zkbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:electric-cord-1-solid" {...props}></Icon>
