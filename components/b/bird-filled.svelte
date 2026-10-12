<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfns2cw0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfns2cw0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bird-filled" {...props}></Icon>
