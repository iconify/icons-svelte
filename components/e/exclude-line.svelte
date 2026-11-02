<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnx3shbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnx3shbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exclude-line" {...props}></Icon>
