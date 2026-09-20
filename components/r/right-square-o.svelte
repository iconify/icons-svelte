<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwmoskb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fwmoskb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:right-square-o" {...props}></Icon>
