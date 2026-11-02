<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgsyako9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgsyako9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:headphone-2-line" {...props}></Icon>
