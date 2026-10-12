<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5sc_7bxe.css';
import '../../css/f/f6dfnknsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5sc_7bxe"/><path clip-rule="evenodd" class="f6dfnknsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gift-filled" {...props}></Icon>
