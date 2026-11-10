<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dktvvbced.css';
import '../../css/m/msy_44tas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dktvvbced"/><path clip-rule="evenodd" class="msy_44tas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-pen-filled" {...props}></Icon>
