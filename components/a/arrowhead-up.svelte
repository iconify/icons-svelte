<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwlck4bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwlck4bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrowhead-up" {...props}></Icon>
