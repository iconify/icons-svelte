<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/ve1apgbwp.css';
import '../../css/k/kskhodb0a.css';
import '../../css/x/x1mnnibkw.css';
import '../../css/z/zlkmtxb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ve1apgbwp"/><path class="kskhodb0a"/><path class="x1mnnibkw"/><path class="zlkmtxb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hand-coins-duotone" {...props}></Icon>
