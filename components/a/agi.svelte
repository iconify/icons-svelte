<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d49fq3bfw.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/t/tnzfzpi4d.css';
import '../../css/t/tzj4vqbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="d49fq3bfw"/><g class="n1mjunbsu"><path class="tnzfzpi4d"/><path class="tzj4vqbyx"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:agi" {...props}></Icon>
