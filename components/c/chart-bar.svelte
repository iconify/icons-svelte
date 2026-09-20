<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh2tvfbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jh2tvfbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:chart-bar" {...props}></Icon>
