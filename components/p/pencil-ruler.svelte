<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piznlmb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piznlmb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pencil-ruler" {...props}></Icon>
