<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6p8dpbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6p8dpbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:intersect-line" {...props}></Icon>
