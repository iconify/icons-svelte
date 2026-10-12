<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9x3p0-sd.css';
import '../../css/k/k58cg2bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9x3p0-sd"/><path class="k58cg2bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:houses-filled" {...props}></Icon>
