<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moyoz5fkv.css';
import '../../css/b/bxl-xsb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="bxl-xsb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:robot-vacuum-48-bold" {...props}></Icon>
