<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6p5qprxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6p5qprxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:download-x" {...props}></Icon>
