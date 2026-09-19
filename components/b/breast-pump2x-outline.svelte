<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wrpbjb6cy.css';
import '../../css/x/xrd-u7syi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wrpbjb6cy"/><path clip-rule="evenodd" class="xrd-u7syi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:breast-pump2x-outline" {...props}></Icon>
