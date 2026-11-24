<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfl-fcnvq.css';
import '../../css/v/vbvjxkbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfl-fcnvq"/><path class="vbvjxkbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:biohazard-filled" {...props}></Icon>
