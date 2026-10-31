<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nonu48a3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nonu48a3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:close-bulk-round" {...props}></Icon>
