<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2-cq6prt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2-cq6prt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mewe" {...props}></Icon>
