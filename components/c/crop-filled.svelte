<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv8c1bcfz.css';
import '../../css/w/wvb1r7csl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8c1bcfz"/><path clip-rule="evenodd" class="wvb1r7csl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:crop-filled" {...props}></Icon>
