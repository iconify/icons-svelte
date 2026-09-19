<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as-6o-bsz.css';
import '../../css/x/x48sfiyvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="as-6o-bsz"/><path class="x48sfiyvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:devices-filled" {...props}></Icon>
