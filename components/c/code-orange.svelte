<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mghtvdb9z.css';
import '../../css/s/s_h41w30n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mghtvdb9z"/><path class="s_h41w30n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:code-orange" {...props}></Icon>
