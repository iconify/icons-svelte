<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubvbjccir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubvbjccir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mars-stroke-fill" {...props}></Icon>
