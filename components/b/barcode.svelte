<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvh2dc16q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvh2dc16q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:barcode" {...props}></Icon>
