<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvc4pqvny.css';
import '../../css/k/kmd5mubrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvc4pqvny"/><path class="kmd5mubrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-calendar-date" {...props}></Icon>
