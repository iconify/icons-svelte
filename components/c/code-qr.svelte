<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s-6b-h1do.css';
import '../../css/h/h0mz56qad.css';
import '../../css/w/wtotfkwny.css';
import '../../css/b/bkqrqjg7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s-6b-h1do"/><path class="h0mz56qad"/><path class="wtotfkwny"/><path class="bkqrqjg7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:code-qr" {...props}></Icon>
