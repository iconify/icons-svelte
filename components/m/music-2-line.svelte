<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyh90f7mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyh90f7mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-2-line" {...props}></Icon>
