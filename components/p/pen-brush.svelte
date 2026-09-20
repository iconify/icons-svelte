<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rdvkx2b8r.css';
import '../../css/g/g5el1zaty.css';
import '../../css/u/uuo1u8bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rdvkx2b8r"/><path class="g5el1zaty"/><path class="uuo1u8bhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pen-brush" {...props}></Icon>
