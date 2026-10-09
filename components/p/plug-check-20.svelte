<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9d7--bko.css';
import '../../css/o/ogzzhkfdn.css';
import '../../css/d/ddzvqdr7g.css';
import '../../css/m/mg--uz6gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a9d7--bko"/><path class="ogzzhkfdn"/><path class="ddzvqdr7g"/><path class="mg--uz6gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-check-20" {...props}></Icon>
