<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyt4yhbtg.css';
import '../../css/p/p4ej_wfwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oyt4yhbtg"/><path class="p4ej_wfwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-bold-duotone" {...props}></Icon>
