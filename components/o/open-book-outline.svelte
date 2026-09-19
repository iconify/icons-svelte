<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/s4ecatbza.css';
import '../../css/a/agdtmdb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="open-book-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="s4ecatbza"/><path class="agdtmdb_i"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:open-book-outline" {...props}></Icon>
