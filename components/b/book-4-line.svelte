<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyi909uom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyi909uom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-4-line" {...props}></Icon>
