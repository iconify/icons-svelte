<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls1c0037m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls1c0037m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carets-from-axis-horizontal-filled" {...props}></Icon>
