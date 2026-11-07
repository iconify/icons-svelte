<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd5gzltfq.css';
import '../../css/h/ha8ssyboi.css';
import '../../css/f/ftsububcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd5gzltfq"/><path class="ha8ssyboi"/><path class="ftsububcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-with-files-bold-duotone" {...props}></Icon>
