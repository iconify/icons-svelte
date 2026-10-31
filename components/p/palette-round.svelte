<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngxjcr4ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngxjcr4ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:palette-round" {...props}></Icon>
