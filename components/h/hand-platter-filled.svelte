<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb94g1vcp.css';
import '../../css/o/o5nyr_biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gb94g1vcp"/><path class="o5nyr_biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hand-platter-filled" {...props}></Icon>
