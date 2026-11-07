<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd5gzltfq.css';
import '../../css/x/x4h7aul0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd5gzltfq"/><path class="x4h7aul0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-dot-bold-duotone" {...props}></Icon>
