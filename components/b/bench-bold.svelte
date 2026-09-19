<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psqq1nb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="psqq1nb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bench-bold" {...props}></Icon>
