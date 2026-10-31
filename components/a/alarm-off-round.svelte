<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j51q_13wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j51q_13wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:alarm-off-round" {...props}></Icon>
