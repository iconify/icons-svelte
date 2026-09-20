<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utl2tvf5z.css';
import '../../css/m/mpy7uabqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utl2tvf5z"/><path class="mpy7uabqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:agix" {...props}></Icon>
