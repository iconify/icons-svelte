<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gldvn3z1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gldvn3z1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-upload-corner-round" {...props}></Icon>
