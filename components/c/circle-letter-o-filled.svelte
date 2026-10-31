<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn62sxfmg.css';
import '../../css/q/ql32cplmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn62sxfmg"/><path clip-rule="evenodd" class="ql32cplmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-o-filled" {...props}></Icon>
