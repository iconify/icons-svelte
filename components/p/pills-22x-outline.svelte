<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/emao1kbkd.css';
import '../../css/m/mzmizbcgi.css';
import '../../css/x/xl7cracwe.css';
import '../../css/i/i9jq-5bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="emao1kbkd"/><path clip-rule="evenodd" class="mzmizbcgi"/><path class="xl7cracwe"/><path clip-rule="evenodd" class="i9jq-5bdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pills-22x-outline" {...props}></Icon>
