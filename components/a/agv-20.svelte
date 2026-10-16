<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qia2ord5v.css';
import '../../css/r/reifvraao.css';
import '../../css/j/jbfxwxb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qia2ord5v"/><path class="reifvraao"/><path class="jbfxwxb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:agv-20" {...props}></Icon>
