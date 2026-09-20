<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amgdxw1dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amgdxw1dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-3-line" {...props}></Icon>
