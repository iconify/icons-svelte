<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m9-4k6y9w.css';
import '../../css/p/pf05l3ymp.css';
import '../../css/d/dkfws9ftw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m9-4k6y9w"/><path class="pf05l3ymp wm-a"/><path class="dkfws9ftw wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-sun-rain" {...props}></Icon>
