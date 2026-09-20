<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1cpxe_xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1cpxe_xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-line" {...props}></Icon>
