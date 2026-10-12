<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y32u2fimd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y32u2fimd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hdmi-port-filled" {...props}></Icon>
