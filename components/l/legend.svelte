<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txu7fdbjl.css';
import '../../css/y/y0w45ybdc.css';
import '../../css/m/mwcn4kbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="txu7fdbjl"/><rect class="y0w45ybdc"/><path class="mwcn4kbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:legend" {...props}></Icon>
