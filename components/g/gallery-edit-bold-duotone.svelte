<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwa9eupgf.css';
import '../../css/x/x446f-znb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwa9eupgf"/><path clip-rule="evenodd" class="x446f-znb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-edit-bold-duotone" {...props}></Icon>
