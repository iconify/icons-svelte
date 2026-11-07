<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/encu70b2r.css';
import '../../css/p/pkhtqxbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="encu70b2r"/><path clip-rule="evenodd" class="pkhtqxbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-medicine-bold" {...props}></Icon>
