<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5h4mibrn.css';
import '../../css/b/bopimfhwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5h4mibrn"/><path class="bopimfhwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:beer-off-filled" {...props}></Icon>
