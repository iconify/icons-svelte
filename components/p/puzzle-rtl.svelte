<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb6pms4ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mb6pms4ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:puzzle-rtl" {...props}></Icon>
