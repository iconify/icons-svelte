<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw2yixbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw2yixbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:lightbulb-x" {...props}></Icon>
