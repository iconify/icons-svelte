<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/smvgv0b2x.css';
import '../../css/b/buqc3kb8r.css';
import '../../css/i/im-kzebzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="smvgv0b2x"/><circle class="buqc3kb8r"/><path class="im-kzebzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-staff-one" {...props}></Icon>
