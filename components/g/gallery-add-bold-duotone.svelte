<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5u34vbpt.css';
import '../../css/i/iwa9eupgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5u34vbpt"/><path class="iwa9eupgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-add-bold-duotone" {...props}></Icon>
