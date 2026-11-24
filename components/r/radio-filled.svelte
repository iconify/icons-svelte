<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrlnyzn3k.css';
import '../../css/z/z3hyr2b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrlnyzn3k"/><path class="z3hyr2b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radio-filled" {...props}></Icon>
