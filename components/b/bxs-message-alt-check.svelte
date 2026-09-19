<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0pvblb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0pvblb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-alt-check" {...props}></Icon>
