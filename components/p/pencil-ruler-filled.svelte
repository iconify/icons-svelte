<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mei0sub7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mei0sub7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pencil-ruler-filled" {...props}></Icon>
