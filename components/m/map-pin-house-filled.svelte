<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqaun74ep.css';
import '../../css/g/gv61adbwm.css';
import '../../css/p/pqeizzbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqaun74ep"/><path clip-rule="evenodd" class="gv61adbwm"/><path class="pqeizzbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-house-filled" {...props}></Icon>
