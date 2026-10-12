<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqk8or5gl.css';
import '../../css/a/a913n8goh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqk8or5gl"/><path class="a913n8goh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circuit-board-filled" {...props}></Icon>
