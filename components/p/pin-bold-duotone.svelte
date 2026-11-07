<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nstr2nbrd.css';
import '../../css/m/m4_d5pj1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nstr2nbrd"/><path class="m4_d5pj1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pin-bold-duotone" {...props}></Icon>
