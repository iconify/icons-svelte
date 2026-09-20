<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/h/hj-ui1b9a.css';
import '../../css/e/ecknynbrw.css';
import '../../css/u/uxyxgac4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="hj-ui1b9a"/><path class="ecknynbrw"/><path class="uxyxgac4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:file-dock-add" {...props}></Icon>
