<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nzacwof9r.css';
import '../../css/o/o7kac3b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="loadgin-left-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="nzacwof9r"/><path class="o7kac3b2m"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:loading-left-outline" {...props}></Icon>
