<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghdyryixw.css';
import '../../css/n/n_bg76bsh.css';
import '../../css/q/qva2skqil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ghdyryixw"/><path class="n_bg76bsh"/><path class="qva2skqil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lay-vessel-20" {...props}></Icon>
