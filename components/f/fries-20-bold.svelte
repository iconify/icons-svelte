<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anhhz7k0l.css';
import '../../css/t/tmt5_jlxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="anhhz7k0l"/><path class="tmt5_jlxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fries-20-bold" {...props}></Icon>
