<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arccr3b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="arccr3b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-2-remix" {...props}></Icon>
