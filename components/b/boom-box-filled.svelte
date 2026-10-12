<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muotlpbym.css';
import '../../css/w/ws98rr2bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muotlpbym"/><path clip-rule="evenodd" class="ws98rr2bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:boom-box-filled" {...props}></Icon>
