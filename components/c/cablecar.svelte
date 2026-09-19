<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbqlp8bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbqlp8bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:cablecar" {...props}></Icon>
