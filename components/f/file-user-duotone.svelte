<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e-0vnyb9w.css';
import '../../css/u/uh3jeubfp.css';
import '../../css/n/nnrxwwb2a.css';
import '../../css/c/cvcti8xca.css';
import '../../css/i/i3sr6la4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e-0vnyb9w"/><path class="uh3jeubfp"/><path class="nnrxwwb2a"/><path class="cvcti8xca"/><path class="i3sr6la4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-user-duotone" {...props}></Icon>
