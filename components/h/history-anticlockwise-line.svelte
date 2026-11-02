<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzusml32t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzusml32t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:history-anticlockwise-line" {...props}></Icon>
