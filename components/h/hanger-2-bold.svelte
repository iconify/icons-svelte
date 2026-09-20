<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw23xpb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw23xpb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hanger-2-bold" {...props}></Icon>
