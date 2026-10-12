<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze_k8fjio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_k8fjio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gallery-thumbnails-filled" {...props}></Icon>
