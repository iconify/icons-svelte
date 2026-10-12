<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/crnkz0bag.css';
import '../../css/b/bwusxd8bo.css';
import '../../css/d/d4hr9gupe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="crnkz0bag"/><path class="bwusxd8bo"/><path class="d4hr9gupe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-heart-duotone" {...props}></Icon>
