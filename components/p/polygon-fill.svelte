<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibfx2rwgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibfx2rwgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:polygon-fill" {...props}></Icon>
