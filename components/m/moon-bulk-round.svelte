<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3vv4_k8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3vv4_k8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:moon-bulk-round" {...props}></Icon>
