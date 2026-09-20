<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw_giebst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dw_giebst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:refrigerator-solid" {...props}></Icon>
