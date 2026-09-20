<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq2_qrlix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq2_qrlix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rewind-sharp" {...props}></Icon>
