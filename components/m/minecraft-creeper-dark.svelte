<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brgk90bxs.css';
import '../../css/v/vuh0gsb8g.css';
import '../../css/z/zdpgtwb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brgk90bxs"/><path class="vuh0gsb8g"/><path class="zdpgtwb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minecraft-creeper-dark" {...props}></Icon>
