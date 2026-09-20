<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmfle6btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmfle6btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:apps-2-ai-line" {...props}></Icon>
