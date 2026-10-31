<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc8mw0b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc8mw0b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:desktop-fill-round" {...props}></Icon>
