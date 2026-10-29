<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n4rkzfbtm.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/r/rxp23_3og.css';
import '../../css/b/bnw9o7z0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n4rkzfbtm"/><path class="qr4ochb5c wm-s"/><path class="rxp23_3og"/><path class="bnw9o7z0h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bug-off-duo" {...props}></Icon>
