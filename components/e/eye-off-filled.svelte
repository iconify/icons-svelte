<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbuw4i61g.css';
import '../../css/m/mk20stbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbuw4i61g"/><path class="mk20stbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:eye-off-filled" {...props}></Icon>
