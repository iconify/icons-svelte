<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th8n30upe.css';
import '../../css/m/mjdzrmbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th8n30upe"/><path class="mjdzrmbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flask-conical-off-filled" {...props}></Icon>
