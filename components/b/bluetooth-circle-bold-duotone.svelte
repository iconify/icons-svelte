<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/j/j8nkcq8nt.css';
import '../../css/y/y7jx548qp.css';
import '../../css/k/kwcn3zb7c.css';
import '../../css/j/j0-ydacal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="j8nkcq8nt"/><path class="y7jx548qp"/><path class="kwcn3zb7c"/><path clip-rule="evenodd" class="j0-ydacal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-circle-bold-duotone" {...props}></Icon>
