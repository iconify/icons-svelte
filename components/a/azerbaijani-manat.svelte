<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l18-8umqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l18-8umqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:azerbaijani-manat" {...props}></Icon>
