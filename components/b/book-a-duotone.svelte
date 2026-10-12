<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fnwqvcbpt.css';
import '../../css/s/ssh18kvpm.css';
import '../../css/v/vzllb1bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fnwqvcbpt"/><path class="ssh18kvpm"/><path class="vzllb1bsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-a-duotone" {...props}></Icon>
