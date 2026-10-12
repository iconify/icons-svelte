<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzub7q6ne.css';
import '../../css/j/jtfx71bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lzub7q6ne"/><path class="jtfx71bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:credit-card-filled" {...props}></Icon>
