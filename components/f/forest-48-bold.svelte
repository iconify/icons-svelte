<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wavel16di.css';
import '../../css/c/c07p4-7-o.css';
import '../../css/k/kzltt2bms.css';
import '../../css/d/d6cvwtbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wavel16di"/><path class="c07p4-7-o"/><path class="kzltt2bms"/><path class="d6cvwtbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forest-48-bold" {...props}></Icon>
