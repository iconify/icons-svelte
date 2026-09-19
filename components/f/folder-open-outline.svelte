<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/btwzuobxo.css';
import '../../css/z/zjwhn7b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="folder-open-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="btwzuobxo"/><path class="zjwhn7b_n"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:folder-open-outline" {...props}></Icon>
