<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zef30ob2n.css';
import '../../css/b/baih8hb8v.css';
import '../../css/e/es97pcacw.css';
import '../../css/u/ucogdbb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zef30ob2n"/><path class="baih8hb8v"/><path class="es97pcacw"/><path class="ucogdbb3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-search-duotone" {...props}></Icon>
