<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/b/b8jj4tcxi.css';
import '../../css/c/csdevybdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4vvtk_cw"/><path clip-rule="evenodd" class="b8jj4tcxi"/><path class="csdevybdj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:compass-duotone" {...props}></Icon>
