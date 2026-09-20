<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8k4_jb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t8k4_jb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:camera" {...props}></Icon>
