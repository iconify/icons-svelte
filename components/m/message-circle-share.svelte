<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edtx_g3bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edtx_g3bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-share" {...props}></Icon>
