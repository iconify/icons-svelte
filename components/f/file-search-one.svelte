<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/ftpkt8zyt.css';
import '../../css/u/urh-5wcvp.css';
import '../../css/h/hlbprpbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ftpkt8zyt"/><circle class="urh-5wcvp"/><path class="hlbprpbiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-search-one" {...props}></Icon>
