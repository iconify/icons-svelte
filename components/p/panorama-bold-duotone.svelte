<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iln029b4a.css';
import '../../css/t/twczvmatf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iln029b4a"/><path class="twczvmatf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panorama-bold-duotone" {...props}></Icon>
