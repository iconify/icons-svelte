<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/utfgr2bmj.css';
import '../../css/d/dzw9pdpsm.css';
import '../../css/r/rplcjjj8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="utfgr2bmj"/><rect class="dzw9pdpsm"/><path class="rplcjjj8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:cpu-light" {...props}></Icon>
