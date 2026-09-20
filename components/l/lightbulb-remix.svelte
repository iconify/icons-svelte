<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovf3rrb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ovf3rrb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:lightbulb-remix" {...props}></Icon>
