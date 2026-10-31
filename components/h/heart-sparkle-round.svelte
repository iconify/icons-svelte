<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao0_fxa0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao0_fxa0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-sparkle-round" {...props}></Icon>
