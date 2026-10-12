<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kslho1p0c.css';
import '../../css/l/lizimdblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kslho1p0c"/><path class="lizimdblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-off-filled" {...props}></Icon>
