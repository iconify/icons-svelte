<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/q4bj7xbuk.css';
import '../../css/b/bk8ioe9xt.css';
import '../../css/d/disxecbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="q4bj7xbuk"/><circle class="bk8ioe9xt"/><path class="disxecbqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-staff" {...props}></Icon>
