<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9jq5ybcb.css';
import '../../css/b/bxmkebcbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9jq5ybcb"/><path class="bxmkebcbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-minus" {...props}></Icon>
