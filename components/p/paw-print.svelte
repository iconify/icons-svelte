<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j1d8v-bos.css';
import '../../css/a/a9nbxkhse.css';
import '../../css/c/cnc8kxp4p.css';
import '../../css/p/p235whbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="j1d8v-bos"/><circle class="a9nbxkhse"/><circle class="cnc8kxp4p"/><path class="p235whbik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:paw-print" {...props}></Icon>
