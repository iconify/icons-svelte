<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx-hgebni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx-hgebni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pointer-off-filled" {...props}></Icon>
