<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp4zsc_7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4zsc_7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:egg-off-filled" {...props}></Icon>
