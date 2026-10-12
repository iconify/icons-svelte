<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fer3w3w-u.css';
import '../../css/p/pairkob_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fer3w3w-u"/><path clip-rule="evenodd" class="pairkob_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:keyboard-music-filled" {...props}></Icon>
