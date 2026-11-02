<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqxt5gmua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqxt5gmua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:right-small-line" {...props}></Icon>
