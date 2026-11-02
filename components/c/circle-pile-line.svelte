<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czm6z7bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czm6z7bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-pile-line" {...props}></Icon>
