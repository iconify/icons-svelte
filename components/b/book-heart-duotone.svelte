<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fnwqvcbpt.css';
import '../../css/c/cepmc47wq.css';
import '../../css/p/pwmof2vgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fnwqvcbpt"/><path clip-rule="evenodd" class="cepmc47wq"/><path class="pwmof2vgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-heart-duotone" {...props}></Icon>
