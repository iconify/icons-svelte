<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auv8y4bny.css';
import '../../css/m/mhso12ngf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="auv8y4bny"/><path class="mhso12ngf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-minus-filled" {...props}></Icon>
