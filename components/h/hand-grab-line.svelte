<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ft6gpyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3ft6gpyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-grab-line" {...props}></Icon>
