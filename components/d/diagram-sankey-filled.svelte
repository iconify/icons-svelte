<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inj9pp63n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inj9pp63n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:diagram-sankey-filled" {...props}></Icon>
