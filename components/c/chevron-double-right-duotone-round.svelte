<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8zytob8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8zytob8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-double-right-duotone-round" {...props}></Icon>
