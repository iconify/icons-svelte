<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aoe568bqj.css';
import '../../css/c/cjq0ppbzf.css';
import '../../css/e/es97pcacw.css';
import '../../css/u/ucogdbb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aoe568bqj"/><path class="cjq0ppbzf"/><path class="es97pcacw"/><path class="ucogdbb3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-check-duotone" {...props}></Icon>
