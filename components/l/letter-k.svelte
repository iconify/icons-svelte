<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzx0mkbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzx0mkbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-k" {...props}></Icon>
