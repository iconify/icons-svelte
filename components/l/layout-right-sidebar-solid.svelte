<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuv7_qo5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vuv7_qo5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:layout-right-sidebar-solid" {...props}></Icon>
