<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm1dldagq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm1dldagq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:photo-album-2-fill" {...props}></Icon>
