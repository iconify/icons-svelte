<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u8ivg9b-a.css';
import '../../css/d/dds8dacon.css';
import '../../css/m/mbnbiobpz.css';
import '../../css/l/lu-kft6oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="u8ivg9b-a"/><path class="dds8dacon"/><path class="mbnbiobpz wm-a"/><path class="lu-kft6oz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layers-duo" {...props}></Icon>
