<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oonz2hbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oonz2hbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mosque-filled" {...props}></Icon>
