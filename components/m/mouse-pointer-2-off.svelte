<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gudpb6b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gudpb6b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:mouse-pointer-2-off" {...props}></Icon>
