<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r0_tkgy3d.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/a/aytpqbcgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r0_tkgy3d"/><circle class="h_tsn8bxt"/><path class="aytpqbcgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:floppy-disk-rear" {...props}></Icon>
