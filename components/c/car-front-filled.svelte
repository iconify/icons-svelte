<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh71qnbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rh71qnbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:car-front-filled" {...props}></Icon>
