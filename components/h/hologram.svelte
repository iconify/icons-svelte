<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/o3x7n9lzn.css';
import '../../css/a/akqn6ybtj.css';
import '../../css/l/l8hdyejxo.css';
import '../../css/t/tgs0vfz_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="o3x7n9lzn"/><path class="akqn6ybtj"/><path class="l8hdyejxo"/><path class="tgs0vfz_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hologram" {...props}></Icon>
