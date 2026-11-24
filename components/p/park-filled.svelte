<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng1qcuzik.css';
import '../../css/k/kt2s0db6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1qcuzik"/><path class="kt2s0db6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:park-filled" {...props}></Icon>
