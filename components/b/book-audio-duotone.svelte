<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t4ha8m21s.css';
import '../../css/s/ssh18kvpm.css';
import '../../css/c/ce2pf8b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t4ha8m21s"/><path class="ssh18kvpm"/><path class="ce2pf8b6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-audio-duotone" {...props}></Icon>
