<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs-7ct1jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hs-7ct1jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:memory-stick-filled" {...props}></Icon>
