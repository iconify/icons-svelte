<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9c07i3qc.css';
import '../../css/c/c51f_wf4g.css';
import '../../css/m/mm5pgybwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a9c07i3qc"/><path class="c51f_wf4g"/><path class="mm5pgybwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:factory-20-bold" {...props}></Icon>
