<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg8wz0m-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eg8wz0m-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikipedia" {...props}></Icon>
