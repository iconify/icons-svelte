<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zenmd1bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zenmd1bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-top-line" {...props}></Icon>
