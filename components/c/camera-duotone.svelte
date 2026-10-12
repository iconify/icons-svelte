<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tdq2722ni.css';
import '../../css/a/a8jfprife.css';
import '../../css/g/gbiqb30yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tdq2722ni"/><path class="a8jfprife"/><path class="gbiqb30yi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:camera-duotone" {...props}></Icon>
