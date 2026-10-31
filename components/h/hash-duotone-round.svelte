<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv7d-qbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv7d-qbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hash-duotone-round" {...props}></Icon>
