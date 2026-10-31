<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zotrfkt_o.css';
import '../../css/p/pec0a9bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zotrfkt_o"/><path clip-rule="evenodd" class="pec0a9bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-b-filled" {...props}></Icon>
