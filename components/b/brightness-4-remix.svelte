<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ly8fbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q2ly8fbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:brightness-4-remix" {...props}></Icon>
