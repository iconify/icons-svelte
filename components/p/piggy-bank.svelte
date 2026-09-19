<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwz0i-bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":472};
const content = `<path class="xwz0i-bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:piggy-bank" {...props}></Icon>
