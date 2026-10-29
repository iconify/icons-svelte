<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/c3id47bcu.css';
import '../../css/t/t9o2bbbrp.css';
import '../../css/a/aalr8-b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="c3id47bcu"/><path class="t9o2bbbrp wm-a"/><path class="aalr8-b6s wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pin-off-solid" {...props}></Icon>
