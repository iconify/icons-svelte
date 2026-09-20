<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o51_pm-7x.css';
import '../../css/y/ydjw7j4fv.css';
import '../../css/r/r0wa9gb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o51_pm-7x"/><path class="ydjw7j4fv"/><path class="r0wa9gb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gryt-dark" {...props}></Icon>
