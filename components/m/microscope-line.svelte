<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsso6ht4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsso6ht4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:microscope-line" {...props}></Icon>
