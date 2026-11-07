<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd8bzbml.css';
import '../../css/e/ey6plua8r.css';
import '../../css/x/x4f46-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="ey6plua8r"/><path class="x4f46-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-cloud-bold-duotone" {...props}></Icon>
