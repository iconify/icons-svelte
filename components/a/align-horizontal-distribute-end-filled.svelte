<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs_acsbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs_acsbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-distribute-end-filled" {...props}></Icon>
