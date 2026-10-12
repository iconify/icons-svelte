<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2uborb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2uborb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:line-dot-left-horizontal-filled" {...props}></Icon>
