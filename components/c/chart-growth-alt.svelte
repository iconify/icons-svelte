<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9qh7tbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9qh7tbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:chart-growth-alt" {...props}></Icon>
