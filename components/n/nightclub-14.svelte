<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjgkyqb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mjgkyqb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:nightclub-14" {...props}></Icon>
