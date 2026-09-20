<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjad2qpef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="jjad2qpef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:panel-top" {...props}></Icon>
