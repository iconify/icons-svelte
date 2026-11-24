<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0k9p0bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0k9p0bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:closed-caption-filled" {...props}></Icon>
