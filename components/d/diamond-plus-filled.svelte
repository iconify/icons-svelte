<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esid47bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esid47bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:diamond-plus-filled" {...props}></Icon>
