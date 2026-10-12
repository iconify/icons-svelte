<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2hl1gbca.css';
import '../../css/n/nfvfrmv_u.css';
import '../../css/t/t2kj8u-pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b2hl1gbca"/><path class="nfvfrmv_u"/><path class="t2kj8u-pi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-clock-duotone" {...props}></Icon>
