<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f_pv1tbov.css';
import '../../css/s/sdsnqtvsn.css';
import '../../css/c/che3vpvsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f_pv1tbov"/><path class="sdsnqtvsn"/><path class="che3vpvsq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lamp-light" {...props}></Icon>
