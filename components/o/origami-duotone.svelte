<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/spc8l1bte.css';
import '../../css/j/j4y0ffqca.css';
import '../../css/f/fg6r96b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="spc8l1bte"/><path class="j4y0ffqca"/><path class="fg6r96b-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:origami-duotone" {...props}></Icon>
