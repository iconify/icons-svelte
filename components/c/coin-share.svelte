<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kshc5g-2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kshc5g-2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:coin-share" {...props}></Icon>
