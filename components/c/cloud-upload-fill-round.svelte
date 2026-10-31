<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ndr7b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ndr7b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-upload-fill-round" {...props}></Icon>
