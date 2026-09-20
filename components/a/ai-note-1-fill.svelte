<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_j62hbkk.css';
import '../../css/c/c9v861dmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_j62hbkk"/><path clip-rule="evenodd" class="c9v861dmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-note-1-fill" {...props}></Icon>
