<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocmvvdv7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocmvvdv7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-ai-fill" {...props}></Icon>
