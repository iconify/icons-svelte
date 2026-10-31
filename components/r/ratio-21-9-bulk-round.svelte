<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cibfdeb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cibfdeb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-21-9-bulk-round" {...props}></Icon>
