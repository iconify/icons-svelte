<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hyuv6wu2h.css';
import '../../css/d/ddkudlafx.css';
import '../../css/m/m7o59w0fd.css';
import '../../css/a/a5m6zzbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="hyuv6wu2h"/><path clip-rule="evenodd" class="ddkudlafx"/><path class="m7o59w0fd"/><path class="a5m6zzbwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:people-minus" {...props}></Icon>
