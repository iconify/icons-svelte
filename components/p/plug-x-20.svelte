<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9d7--bko.css';
import '../../css/o/ogzzhkfdn.css';
import '../../css/d/ddzvqdr7g.css';
import '../../css/h/hfunc-u9d.css';
import '../../css/v/vm6ftdb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a9d7--bko"/><path class="ogzzhkfdn"/><path class="ddzvqdr7g"/><path class="hfunc-u9d"/><path class="vm6ftdb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-x-20" {...props}></Icon>
