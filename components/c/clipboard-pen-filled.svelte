<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nauphjpxp.css';
import '../../css/g/grxjc5bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nauphjpxp"/><path clip-rule="evenodd" class="grxjc5bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-pen-filled" {...props}></Icon>
