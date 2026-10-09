<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrit7jbhb.css';
import '../../css/r/r92287bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jrit7jbhb"/><path class="r92287bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eraser-20" {...props}></Icon>
