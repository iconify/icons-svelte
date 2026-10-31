<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clu1kebvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clu1kebvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-download-fill-round" {...props}></Icon>
