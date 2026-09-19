<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us1ea67dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="us1ea67dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-doc" {...props}></Icon>
