<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5mhyjbwd.css';
import '../../css/t/tq10f7bbh.css';
import '../../css/h/h-e9_jbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y5mhyjbwd"/><path class="tq10f7bbh"/><path class="h-e9_jbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-famibot" {...props}></Icon>
