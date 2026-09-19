<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hti5hofyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hti5hofyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-dots-vertical" {...props}></Icon>
