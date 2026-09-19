<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e49olqbuq.css';
import '../../css/m/m3ouxln2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e49olqbuq"/><path clip-rule="evenodd" class="m3ouxln2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-experince-design-solid" {...props}></Icon>
