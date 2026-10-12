<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klzrc_ihu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klzrc_ihu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-exclamation-point-filled" {...props}></Icon>
