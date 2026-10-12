<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw_jelzmb.css';
import '../../css/l/l_fae7rzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw_jelzmb"/><path class="l_fae7rzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-input-filled" {...props}></Icon>
