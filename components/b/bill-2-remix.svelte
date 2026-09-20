<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0hu3wbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s0hu3wbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bill-2-remix" {...props}></Icon>
