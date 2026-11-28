<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw3b5p53b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw3b5p53b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:garage-check" {...props}></Icon>
