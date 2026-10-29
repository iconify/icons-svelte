<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ain1tnbxt.css';
import '../../css/s/sy7kpcbuo.css';
import '../../css/q/qdzstlt9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ain1tnbxt"/><path class="sy7kpcbuo wm-a"/><path class="qdzstlt9t wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:image-sparkles" {...props}></Icon>
