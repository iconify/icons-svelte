<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dccqsobpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dccqsobpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:puzzle-ltr" {...props}></Icon>
