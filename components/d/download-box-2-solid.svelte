<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw_ax30_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zw_ax30_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:download-box-2-solid" {...props}></Icon>
