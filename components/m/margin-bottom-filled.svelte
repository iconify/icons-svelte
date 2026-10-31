<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3sr-eg0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3sr-eg0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:margin-bottom-filled" {...props}></Icon>
