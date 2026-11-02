<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebj4j99dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebj4j99dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-minus-corner-line" {...props}></Icon>
