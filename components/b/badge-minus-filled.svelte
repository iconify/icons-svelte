<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6k2dc_jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6k2dc_jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-minus-filled" {...props}></Icon>
