<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0j_qj-1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w0j_qj-1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:heart-outline" {...props}></Icon>
