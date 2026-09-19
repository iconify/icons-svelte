<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyoj2sb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyoj2sb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-quote-alt-left" {...props}></Icon>
