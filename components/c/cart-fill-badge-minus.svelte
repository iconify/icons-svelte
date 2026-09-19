<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q841-ov0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q841-ov0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cart-fill-badge-minus" {...props}></Icon>
