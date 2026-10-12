<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-b_8bcwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-b_8bcwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:diamond-filled" {...props}></Icon>
