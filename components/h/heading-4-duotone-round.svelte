<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsh2ghnfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsh2ghnfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-4-duotone-round" {...props}></Icon>
