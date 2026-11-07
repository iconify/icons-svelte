<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxi8hkb5i.css';
import '../../css/u/uu0gpbbvf.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/y/ynv6fkb2h.css';
import '../../css/f/fd9mfdh9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxi8hkb5i"/><path clip-rule="evenodd" class="uu0gpbbvf"/><g class="xtpeb-edw"><path class="ynv6fkb2h"/><path class="fd9mfdh9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hiking-bold-duotone" {...props}></Icon>
