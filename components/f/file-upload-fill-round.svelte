<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0pvlhbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0pvlhbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-upload-fill-round" {...props}></Icon>
