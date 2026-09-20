<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/n/nnccshiyx.css';
import '../../css/c/c7cra2b-g.css';
import '../../css/e/e0hfau-no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="nnccshiyx"/><path class="c7cra2b-g"/><path class="e0hfau-no"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-alt-light" {...props}></Icon>
