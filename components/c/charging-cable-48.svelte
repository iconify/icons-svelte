<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r72vqtbkc.css';
import '../../css/s/sy67f09qo.css';
import '../../css/x/xyec1nbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r72vqtbkc"/><path class="sy67f09qo"/><path class="xyec1nbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-cable-48" {...props}></Icon>
