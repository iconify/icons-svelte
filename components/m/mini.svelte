<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkdzgcbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkdzgcbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mini" {...props}></Icon>
