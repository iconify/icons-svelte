<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p319hddsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p319hddsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bookmark-active" {...props}></Icon>
