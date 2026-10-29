<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebl5rib_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebl5rib_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-check-solid" {...props}></Icon>
