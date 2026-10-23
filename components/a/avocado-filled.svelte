<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8j_evhcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8j_evhcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:avocado-filled" {...props}></Icon>
