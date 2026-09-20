<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/e/e-2ge42fi.css';
import '../../css/l/llfj4f_hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="n1mjunbsu"><path clip-rule="evenodd" class="e-2ge42fi"/><path class="llfj4f_hk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:devto-dark" {...props}></Icon>
