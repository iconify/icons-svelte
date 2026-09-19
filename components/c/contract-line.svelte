<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy-4x9bfo.css';
import '../../css/p/pb7t6bclw.css';
import '../../css/t/tvu3xz-hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="xy-4x9bfo"/><path class="pb7t6bclw"/><path class="tvu3xz-hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:contract-line" {...props}></Icon>
