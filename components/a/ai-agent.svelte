<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3t5d0bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3t5d0bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ai-agent" {...props}></Icon>
