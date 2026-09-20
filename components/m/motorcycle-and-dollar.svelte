<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq0mikcbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tq0mikcbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-dollar" {...props}></Icon>
