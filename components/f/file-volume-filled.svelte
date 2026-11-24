<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5jau6bgw.css';
import '../../css/j/j22w93are.css';
import '../../css/p/pndt6mbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5jau6bgw"/><path class="j22w93are"/><path class="pndt6mbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-volume-filled" {...props}></Icon>
