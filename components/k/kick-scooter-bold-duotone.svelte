<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pklythb1b.css';
import '../../css/x/x2jcmsnbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pklythb1b"/><path clip-rule="evenodd" class="x2jcmsnbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kick-scooter-bold-duotone" {...props}></Icon>
