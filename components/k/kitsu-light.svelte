<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-zmabdk.css';
import '../../css/r/rrklbmuzh.css';
import '../../css/z/zem9k1eun.css';
import '../../css/t/tjho2_-dd.css';
import '../../css/m/mebo6qfse.css';
import '../../css/k/kmsf33cda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-zmabdk"/><path class="rrklbmuzh"/><path class="zem9k1eun"/><path class="tjho2_-dd"/><path class="mebo6qfse"/><path class="kmsf33cda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kitsu-light" {...props}></Icon>
