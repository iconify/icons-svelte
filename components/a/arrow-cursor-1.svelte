<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buos942us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="buos942us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-cursor-1" {...props}></Icon>
