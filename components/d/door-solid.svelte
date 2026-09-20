<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww36-hbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ww36-hbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:door-solid" {...props}></Icon>
