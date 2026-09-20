<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/modwem2lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="modwem2lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:arrows-alt" {...props}></Icon>
