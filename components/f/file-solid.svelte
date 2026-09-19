<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0vgceb-l.css';
import '../../css/c/cnllsbb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0vgceb-l"/><path class="cnllsbb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:file-solid" {...props}></Icon>
