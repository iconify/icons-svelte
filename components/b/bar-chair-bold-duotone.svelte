<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhgdmdlsz.css';
import '../../css/u/u-6gmvb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhgdmdlsz"/><path class="u-6gmvb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bar-chair-bold-duotone" {...props}></Icon>
