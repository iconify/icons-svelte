<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goohnvfrd.css';
import '../../css/z/z8ck8jbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="goohnvfrd"/><path class="z8ck8jbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:file" {...props}></Icon>
