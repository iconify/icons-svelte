<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etj_qccda.css';
import '../../css/x/xz53smi8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etj_qccda"/><path class="xz53smi8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:book-content" {...props}></Icon>
