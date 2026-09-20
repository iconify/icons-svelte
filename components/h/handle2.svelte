<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4_whwpzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k4_whwpzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:handle2" {...props}></Icon>
