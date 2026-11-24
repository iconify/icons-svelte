<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qixv8v0ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qixv8v0ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carets-from-axis-dashed-horizontal-filled" {...props}></Icon>
