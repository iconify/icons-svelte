<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjp174btb.css';
import '../../css/f/fhnwp1bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjp174btb"/><path class="fhnwp1bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-arrow-bold" {...props}></Icon>
