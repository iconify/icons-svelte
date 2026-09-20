<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb589rkmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb589rkmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cursor-drag" {...props}></Icon>
