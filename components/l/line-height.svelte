<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u34p5im3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u34p5im3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:line-height" {...props}></Icon>
