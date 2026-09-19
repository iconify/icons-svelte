<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/q4bj7xbuk.css';
import '../../css/w/wwi2rp7cw.css';
import '../../css/s/s8iooiy8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="q4bj7xbuk"/><path class="wwi2rp7cw"/><circle class="s8iooiy8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-music" {...props}></Icon>
