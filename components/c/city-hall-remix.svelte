<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-q_4i3gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e-q_4i3gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:city-hall-remix" {...props}></Icon>
