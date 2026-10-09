<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apb_dgbpm.css';
import '../../css/v/vw3o48bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="apb_dgbpm"/><path class="vw3o48bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microgrid-48-bold" {...props}></Icon>
