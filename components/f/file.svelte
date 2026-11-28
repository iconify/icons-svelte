<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py8bx-zrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py8bx-zrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file" {...props}></Icon>
