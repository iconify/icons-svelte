<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lds95vbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lds95vbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-flip-vertical" {...props}></Icon>
