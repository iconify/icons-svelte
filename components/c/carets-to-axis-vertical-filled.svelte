<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt_n8sqbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_n8sqbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carets-to-axis-vertical-filled" {...props}></Icon>
