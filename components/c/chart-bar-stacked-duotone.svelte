<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m60fi_bcv.css';
import '../../css/a/a814_vg9v.css';
import '../../css/n/nj4qihbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m60fi_bcv"/><path class="a814_vg9v"/><path class="nj4qihbbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-bar-stacked-duotone" {...props}></Icon>
