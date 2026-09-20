<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfbuyzb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfbuyzb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-dashed-panel" {...props}></Icon>
