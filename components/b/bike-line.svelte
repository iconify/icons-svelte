<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tofxyuz8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tofxyuz8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bike-line" {...props}></Icon>
