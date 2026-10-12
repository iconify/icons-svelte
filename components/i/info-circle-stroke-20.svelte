<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4g_2gbsf.css';
import '../../css/v/vixdv7vsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g4g_2gbsf"/><path class="vixdv7vsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:info-circle-stroke-20" {...props}></Icon>
