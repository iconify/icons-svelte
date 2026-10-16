<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm_-_fgwp.css';
import '../../css/k/kicqyzbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gm_-_fgwp"/><path class="kicqyzbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-rod-48" {...props}></Icon>
