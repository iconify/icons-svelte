<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp3507b3q.css';
import '../../css/m/mef_eabep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp3507b3q"/><path class="mef_eabep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-building-house" {...props}></Icon>
