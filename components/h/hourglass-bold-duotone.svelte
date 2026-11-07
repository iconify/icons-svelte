<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g48ucxnqe.css';
import '../../css/i/im3g8pbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g48ucxnqe"/><path class="im3g8pbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hourglass-bold-duotone" {...props}></Icon>
