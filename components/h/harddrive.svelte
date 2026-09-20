<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w01qq6qdq.css';
import '../../css/m/m_r-rybts.css';
import '../../css/u/uvd1g15ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="rotate(-90 10 8)" class="bi12bsetm"><path class="w01qq6qdq"/><circle class="m_r-rybts"/><path class="uvd1g15ov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:harddrive" {...props}></Icon>
