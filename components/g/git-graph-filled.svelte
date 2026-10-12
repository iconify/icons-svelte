<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z69-ohbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z69-ohbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-graph-filled" {...props}></Icon>
