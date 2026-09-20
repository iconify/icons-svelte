<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk8q7na1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xk8q7na1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-edit-robot-remix" {...props}></Icon>
