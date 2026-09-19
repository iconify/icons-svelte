<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mdbfn1bya.css';
import '../../css/m/mlyzuub0m.css';
import '../../css/e/egneazb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="mdbfn1bya"/><path class="mlyzuub0m"/><path class="egneazb5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:file-arrow-down-left" {...props}></Icon>
