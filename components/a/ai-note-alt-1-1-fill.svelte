<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll_k45b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ll_k45b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-note-alt-1-1-fill" {...props}></Icon>
