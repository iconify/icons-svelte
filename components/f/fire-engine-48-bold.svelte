<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiecv_t_z.css';
import '../../css/w/wryrt8b-k.css';
import '../../css/c/cm6td6aoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aiecv_t_z"/><path class="wryrt8b-k"/><path class="cm6td6aoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-engine-48-bold" {...props}></Icon>
